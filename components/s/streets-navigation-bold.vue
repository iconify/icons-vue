<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa4c_mbug.css';
import '../../css/j/juwk50edv.css';
import '../../css/p/p6myf1z6f.css';
import '../../css/x/xt-xue_6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4c_mbug"/><path class="juwk50edv"/><path class="p6myf1z6f"/><path class="xt-xue_6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-bold" /></template>
