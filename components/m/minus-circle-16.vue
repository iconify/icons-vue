<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn_x7fxrw.css';
import '../../css/n/n4_12dd-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sn_x7fxrw"/><path clip-rule="evenodd" class="n4_12dd-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:minus-circle-16" /></template>
