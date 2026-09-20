<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2mq70njp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t2mq70njp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tornado" /></template>
