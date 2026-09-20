<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1hwcrbsr.css';
import '../../css/r/rdjvdkbbm.css';
import '../../css/e/e1fsegbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c1hwcrbsr"/><circle class="rdjvdkbbm"/><circle class="e1fsegbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-anonymous" /></template>
