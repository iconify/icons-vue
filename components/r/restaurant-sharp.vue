<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtu_bi9-n.css';
import '../../css/p/puxz7qb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtu_bi9-n"/><path class="puxz7qb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:restaurant-sharp" /></template>
