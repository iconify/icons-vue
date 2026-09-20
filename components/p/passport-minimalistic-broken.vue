<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/snm6yibit.css';
import '../../css/g/ga7t0girt.css';
import '../../css/z/z__w1mbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="snm6yibit"/><path class="ga7t0girt"/><path class="z__w1mbdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-minimalistic-broken" /></template>
