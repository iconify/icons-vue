<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r5tlskk2v.css';
import '../../css/c/c318wxfqg.css';
import '../../css/m/m9zkpabmw.css';
import '../../css/b/bgqoji13c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhr7QBbVO"><g class="ufeehvblu"><path class="r5tlskk2v"/><path class="c318wxfqg"/><path class="m9zkpabmw"/><path class="bgqoji13c"/></g></mask></defs><path mask="url(#SVGhr7QBbVO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:stopwatch-start" /></template>
