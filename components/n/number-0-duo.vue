<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sarxmn0sl.css';
import '../../css/l/lnc1wrb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sarxmn0sl secondary"/><path class="lnc1wrb5i primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-0-duo" /></template>
