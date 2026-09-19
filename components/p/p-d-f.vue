<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/busl-3uwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="busl-3uwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:p-d-f" /></template>
