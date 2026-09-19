<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl1h56gff.css';
import '../../css/z/zoh-vz08z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl1h56gff"/><path class="zoh-vz08z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shake-outline" /></template>
