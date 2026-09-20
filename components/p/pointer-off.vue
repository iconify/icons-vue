<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0eo5abtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0eo5abtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-off" /></template>
