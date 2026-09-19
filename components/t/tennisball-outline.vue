<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnii4hccr.css';
import '../../css/f/f345gcb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rnii4hccr"/><path class="f345gcb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:tennisball-outline" /></template>
