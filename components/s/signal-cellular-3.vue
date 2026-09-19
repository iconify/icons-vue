<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avrykfb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avrykfb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:signal-cellular-3" /></template>
