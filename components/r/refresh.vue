<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ing4w0e.css';
import '../../css/j/jqvw4p60w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="v4ing4w0e"/><path class="jqvw4p60w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:refresh" /></template>
