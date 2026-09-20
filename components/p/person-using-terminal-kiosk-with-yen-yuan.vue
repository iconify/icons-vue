<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjnvd49sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gjnvd49sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-yen-yuan" /></template>
