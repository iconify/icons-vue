<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lloikpa_g.css';
import '../../css/g/glhuhnb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lloikpa_g"/><path class="glhuhnb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:power-sharp" /></template>
