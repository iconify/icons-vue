<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/al5y9rb2i.css';
import '../../css/n/n90jsqger.css';
import '../../css/z/z0nf3jbvl.css';
import '../../css/x/x50dneb7t.css';
import '../../css/u/usbqyjips.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="al5y9rb2i"/><path class="n90jsqger"/><path class="z0nf3jbvl"/><path class="x50dneb7t"/><path class="usbqyjips"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:peer-to-peer-03" /></template>
