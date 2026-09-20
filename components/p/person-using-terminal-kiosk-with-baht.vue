<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0opr_u6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b0opr_u6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-baht" /></template>
