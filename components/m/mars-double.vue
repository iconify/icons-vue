<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6en0pyme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="l6en0pyme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mars-double" /></template>
