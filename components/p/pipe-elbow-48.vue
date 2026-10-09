<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur1gjzh2v.css';
import '../../css/u/uaklp-bbr.css';
import '../../css/e/ekmag7bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur1gjzh2v"/><path class="uaklp-bbr"/><path class="ekmag7bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-elbow-48" /></template>
