<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r5tlskk2v.css';
import '../../css/e/el5co48gm.css';
import '../../css/q/qk9ee1x_u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRMaSpcHZ"><g class="ufeehvblu"><path class="r5tlskk2v"/><path class="el5co48gm"/><path class="qk9ee1x_u"/></g></mask></defs><path mask="url(#SVGRMaSpcHZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:stopwatch" /></template>
