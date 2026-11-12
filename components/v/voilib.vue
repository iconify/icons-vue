<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idb1z9zzg.css';
import '../../css/k/kyzfwv8lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="idb1z9zzg"/><path class="kyzfwv8lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voilib" /></template>
