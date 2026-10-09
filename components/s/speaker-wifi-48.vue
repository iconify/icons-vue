<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trh7j8bwt.css';
import '../../css/t/tkwuedbzn.css';
import '../../css/s/sifm99blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trh7j8bwt"/><path class="tkwuedbzn"/><path class="sifm99blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speaker-wifi-48" /></template>
