<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-p-4-vc.css';
import '../../css/k/ku8eyo-db.css';
import '../../css/x/xl_woxbbd.css';
import '../../css/u/ujnu3os2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGHhpq3ccw" x1="256" x2="256" y1="13.4" y2="498.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="b5-p-4-vc"/><stop offset="1" class="ku8eyo-db"/></linearGradient><path fill="url(#SVGHhpq3ccw)" class="xl_woxbbd"/><path class="ujnu3os2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2013" /></template>
