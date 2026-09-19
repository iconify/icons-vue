<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k188_sbpi.css';
import '../../css/f/f7bma5brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k188_sbpi"/><circle class="f7bma5brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:security-command-center" /></template>
