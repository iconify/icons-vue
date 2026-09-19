<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rkuavfbpw.css';
import '../../css/g/gvjpz8u1b.css';
import '../../css/o/o1m2sbc1u.css';
import '../../css/r/rbs0pvi1u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDLyaheEO"><g class="ft5dv1b6b"><path class="rkuavfbpw"/><path class="gvjpz8u1b"/><path class="o1m2sbc1u"/><path class="rbs0pvi1u"/></g></mask></defs><path mask="url(#SVGDLyaheEO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:remind-disable" /></template>
