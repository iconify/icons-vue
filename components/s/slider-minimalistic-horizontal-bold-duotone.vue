<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy178tbuh.css';
import '../../css/s/skftdzbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy178tbuh"/><path class="skftdzbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-minimalistic-horizontal-bold-duotone" /></template>
