<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apfv19-nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apfv19-nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rede-bandeirantes" /></template>
