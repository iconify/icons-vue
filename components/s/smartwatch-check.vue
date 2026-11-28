<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq8g1iq7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq8g1iq7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartwatch-check" /></template>
