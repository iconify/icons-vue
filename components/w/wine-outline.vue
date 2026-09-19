<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofjs243ce.css';
import '../../css/h/ho71zpbvj.css';
import '../../css/i/idfn3mciq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ofjs243ce"/><path class="ho71zpbvj"/><path class="idfn3mciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wine-outline" /></template>
