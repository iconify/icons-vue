<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5zefg.css';
import '../../css/s/sg9f1f.css';
import '../../css/y/ydovum.css';
import '../../css/q/qchkvb.css';
import '../../css/s/so-from-42.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/d/d-zdr4ap.css';
import '../../css/d/d-1z8qst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5zefg"/><circle class="sg9f1f ydovum"/><path class="qchkvb ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-radius" /></template>
