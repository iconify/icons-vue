<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ozgtmbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ozgtmbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-add-01" /></template>
