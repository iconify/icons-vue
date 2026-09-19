<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqbx0oy5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqbx0oy5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:menu-sharp" /></template>
