<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no0jgnb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="no0jgnb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mobile-screen" /></template>
