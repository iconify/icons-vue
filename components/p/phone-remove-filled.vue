<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/x/xr5osn.css';
import '../../css/f/f6m63a.css';
import '../../css/y/y4wbml.css';
import '../../css/f/f2fjgc.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew xr5osn"/><path class="f6m63a iw1iew y4wbml"/><path class="f2fjgc iw1iew y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:phone-remove-filled" /></template>
