<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm-4lxb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rm-4lxb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:no-one-under-eighteen-symbol-filled" /></template>
