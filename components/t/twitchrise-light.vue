<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzxmpdi0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzxmpdi0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitchrise-light" /></template>
