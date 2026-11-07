<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snl37hbbd.css';
import '../../css/r/rgo7s3bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snl37hbbd"/><path class="rgo7s3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-outline" /></template>
