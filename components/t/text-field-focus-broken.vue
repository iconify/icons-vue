<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wp-9pxbpn.css';
import '../../css/b/bpkt4gbdh.css';
import '../../css/o/om4lnzbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wp-9pxbpn"/><path class="bpkt4gbdh"/><path class="om4lnzbpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-focus-broken" /></template>
