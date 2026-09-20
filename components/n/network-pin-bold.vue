<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvmmamb2n.css';
import '../../css/k/kiom4-bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvmmamb2n"/><path class="kiom4-bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:network-pin-bold" /></template>
