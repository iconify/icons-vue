<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvs2q08pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lvs2q08pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-right-header" /></template>
