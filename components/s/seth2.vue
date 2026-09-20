<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sthgrmhos.css';
import '../../css/p/pcus4nb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sthgrmhos"/><path class="pcus4nb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:seth2" /></template>
