<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b572sebbf.css';
import '../../css/s/sqgcj3ezp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b572sebbf"/><path class="sqgcj3ezp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:repeat-one-16" /></template>
