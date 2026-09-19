<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxkvfd2yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxkvfd2yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:user-x" /></template>
