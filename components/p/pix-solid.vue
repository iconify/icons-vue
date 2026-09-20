<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb444nbdj.css';
import '../../css/u/uj-pmt-ih.css';
import '../../css/r/rlbz7sbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb444nbdj"/><path class="uj-pmt-ih"/><path class="rlbz7sbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pix-solid" /></template>
