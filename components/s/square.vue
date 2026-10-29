<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mun6vbc9f.css';
import '../../css/n/nuczxhi4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mun6vbc9f"/><path class="nuczxhi4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:square" /></template>
