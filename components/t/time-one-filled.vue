<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0b6dl7uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0b6dl7uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:time-one-filled" /></template>
