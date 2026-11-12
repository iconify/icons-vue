<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph--6ybee.css';
import '../../css/o/oemvvsbfu.css';
import '../../css/k/k8-noccie.css';
import '../../css/u/urkmcdwfb.css';
import '../../css/y/yz7raabqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ph--6ybee"/><path class="oemvvsbfu"/><path class="k8-noccie"/><path class="urkmcdwfb"/><path class="yz7raabqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-dark" /></template>
