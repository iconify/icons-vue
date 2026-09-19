<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apjs5gb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="apjs5gb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:slack-wordmark" /></template>
