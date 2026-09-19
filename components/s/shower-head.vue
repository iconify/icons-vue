<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk93phdge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk93phdge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shower-head" /></template>
