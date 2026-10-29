<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mypcxdb2j.css';
import '../../css/g/g3ln1eoob.css';
import '../../css/g/gmaorj__k.css';
import '../../css/s/saup0_b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mypcxdb2j wm-a"/><path class="g3ln1eoob wm-k"/><path class="gmaorj__k wm-k"/><path class="saup0_b6w wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:taxi" /></template>
