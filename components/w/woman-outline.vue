<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft8aas7is.css';
import '../../css/h/h_gg3_bew.css';
import '../../css/o/o0lqhvmmi.css';
import '../../css/k/k8brvnbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ft8aas7is"/><path class="h_gg3_bew"/><circle class="o0lqhvmmi"/><path class="k8brvnbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:woman-outline" /></template>
