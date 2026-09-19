<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owp543m0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="owp543m0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:wifi" /></template>
