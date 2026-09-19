<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5yrbob0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s5yrbob0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:zendesk-fill-12" /></template>
