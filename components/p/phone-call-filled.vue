<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_mz_z.css';
import '../../css/i/iw1iew.css';
import '../../css/l/lycpvr.css';
import '../../css/y/y4wbml.css';
import '../../css/s/sxou1t.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_mz_z iw1iew"/><path class="iw1iew lycpvr y4wbml"/><path class="iw1iew sxou1t y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:phone-call-filled" /></template>
