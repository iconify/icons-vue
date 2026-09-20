<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfzotcwxd.css';
import '../../css/e/eart31dpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jfzotcwxd"/><path class="eart31dpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:peso" /></template>
