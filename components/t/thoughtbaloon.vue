<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-ksnhfb.css';
import '../../css/n/nqaiq_lnn.css';
import '../../css/u/uvs2kogds.css';
import '../../css/a/ad6qe92ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="mr-ksnhfb"/><circle class="nqaiq_lnn"/><circle class="uvs2kogds"/><path class="ad6qe92ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:thoughtbaloon" /></template>
