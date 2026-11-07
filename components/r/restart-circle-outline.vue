<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsgb84bvf.css';
import '../../css/q/q1sggqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsgb84bvf"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-circle-outline" /></template>
