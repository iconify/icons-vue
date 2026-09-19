<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ph6jbci.css';
import '../../css/s/st682lbcm.css';
import '../../css/u/us9ytuuie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m1ph6jbci"/><path class="st682lbcm"/><path class="us9ytuuie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:woocommerce" /></template>
