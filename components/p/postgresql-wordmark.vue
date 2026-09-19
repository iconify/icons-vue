<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkx72bus.css';
import '../../css/b/byx4gtwse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hxkx72bus"/><path class="byx4gtwse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:postgresql-wordmark" /></template>
