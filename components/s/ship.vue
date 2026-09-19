<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k150ojlno.css';
import '../../css/o/ol2nzbc1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="k150ojlno"/><path class="ol2nzbc1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ship" /></template>
