<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2vuvdbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2vuvdbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unlock-muted-fill" /></template>
