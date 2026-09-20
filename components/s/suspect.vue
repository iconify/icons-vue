<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-7eu8rv.css';
import '../../css/j/j8qutoidr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v4-7eu8rv"/><path class="j8qutoidr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:suspect" /></template>
