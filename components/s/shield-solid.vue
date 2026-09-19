<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2g4wqbfa.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="a2g4wqbfa clr-i-solid clr-i-solid-path-1"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:shield-solid" /></template>
