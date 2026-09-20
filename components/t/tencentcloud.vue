<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnqxrgaqv.css';
import '../../css/e/eiyo1ccvq.css';
import '../../css/p/pi8rb54jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnqxrgaqv"/><path class="eiyo1ccvq"/><path class="pi8rb54jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tencentcloud" /></template>
