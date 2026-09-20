<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-p-4-vc.css';
import '../../css/k/ku8eyo-db.css';
import '../../css/x/xl_woxbbd.css';
import '../../css/u/ujnu3os2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGJd2vOdGG" x1="256" x2="256" y1="13.435" y2="498.565" gradientUnits="userSpaceOnUse"><stop offset="0" class="b5-p-4-vc"/><stop offset="1" class="ku8eyo-db"/></linearGradient><path fill="url(#SVGJd2vOdGG)" class="xl_woxbbd"/><path class="ujnu3os2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2013" /></template>
