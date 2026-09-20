<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl3uoubvp.css';
import '../../css/b/b6eiwkb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vl3uoubvp"/><circle class="b6eiwkb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-add-rtl" /></template>
