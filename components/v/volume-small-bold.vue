<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg0z4wbgl.css';
import '../../css/k/k0rw3tfwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0z4wbgl"/><path clip-rule="evenodd" class="k0rw3tfwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-small-bold" /></template>
