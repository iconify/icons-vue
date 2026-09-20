<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4jp0udxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4jp0udxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:road-sign-stop" /></template>
