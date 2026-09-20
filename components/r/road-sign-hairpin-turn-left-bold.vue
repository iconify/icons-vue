<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss7r9ybtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7r9ybtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:road-sign-hairpin-turn-left-bold" /></template>
