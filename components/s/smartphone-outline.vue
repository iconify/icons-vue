<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeeel25yq.css';
import '../../css/l/lx933dbek.css';
import '../../css/d/dzzm5i91a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeeel25yq"/><circle class="lx933dbek"/><path class="dzzm5i91a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:smartphone-outline" /></template>
