<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcw9l3bkd.css';
import '../../css/c/cmarxq79e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jcw9l3bkd"/><path class="cmarxq79e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:on-holiday-line" /></template>
