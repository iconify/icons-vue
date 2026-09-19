<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz2ov7bmp.css';
import '../../css/p/p12bzlbrl.css';
import '../../css/j/j24ii1bme.css';
import '../../css/b/bzre8l_um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kz2ov7bmp"/><path class="p12bzlbrl"/><path class="j24ii1bme"/><path class="bzre8l_um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vsphere-wordmark" /></template>
