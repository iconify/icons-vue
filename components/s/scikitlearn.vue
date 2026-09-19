<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtm-4pbpn.css';
import '../../css/d/dh1shqbdr.css';
import '../../css/u/usdnfabrq.css';
import '../../css/z/ze7q12bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gtm-4pbpn"/><path class="dh1shqbdr"/><path class="usdnfabrq"/><path class="ze7q12bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:scikitlearn" /></template>
