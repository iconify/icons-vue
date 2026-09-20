<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g44sicinw.css';
import '../../css/l/l3-5_c46r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g44sicinw"/><path clip-rule="evenodd" class="l3-5_c46r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:polyx" /></template>
