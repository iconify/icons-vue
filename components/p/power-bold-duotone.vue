<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjmcju-mi.css';
import '../../css/p/pvhv_7sne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjmcju-mi"/><path class="pvhv_7sne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:power-bold-duotone" /></template>
