<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2lsgoblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v2lsgoblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-pound" /></template>
