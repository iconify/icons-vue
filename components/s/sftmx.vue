<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_s2gbth.css';
import '../../css/a/amj00lbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_s2gbth"/><path clip-rule="evenodd" class="amj00lbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sftmx" /></template>
