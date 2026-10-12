<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl15a80lp.css';
import '../../css/b/b-i2932jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nl15a80lp"/><path class="b-i2932jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-clock-20" /></template>
