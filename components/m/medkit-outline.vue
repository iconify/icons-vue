<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecffrn81e.css';
import '../../css/z/zzs6n-cer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ecffrn81e"/><path class="zzs6n-cer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:medkit-outline" /></template>
