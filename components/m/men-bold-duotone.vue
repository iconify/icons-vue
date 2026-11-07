<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukbct-jgm.css';
import '../../css/n/n6fnwhbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ukbct-jgm"/><path class="n6fnwhbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:men-bold-duotone" /></template>
