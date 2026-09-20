<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_igc2gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp_igc2gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:namesilo" /></template>
