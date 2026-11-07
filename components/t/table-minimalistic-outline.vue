<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8f365c-u.css';
import '../../css/j/jjp92xbjh.css';
import '../../css/m/mrmmz5sme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8f365c-u"/><path class="jjp92xbjh"/><path class="mrmmz5sme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-minimalistic-outline" /></template>
