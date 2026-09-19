<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udnvig89x.css';
import '../../css/m/mj6sbgtse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udnvig89x"/><path class="mj6sbgtse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speaker" /></template>
