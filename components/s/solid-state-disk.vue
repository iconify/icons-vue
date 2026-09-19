<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-6grdhmq.css';
import '../../css/i/irl6mqbpf.css';
import '../../css/p/pgml1ac6f.css';
import '../../css/x/x-4ht3bod.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtCoQScgc"><g class="ft5dv1b6b"><path class="h-6grdhmq"/><path class="irl6mqbpf"/><path class="pgml1ac6f"/><path class="x-4ht3bod"/></g></mask></defs><path mask="url(#SVGtCoQScgc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:solid-state-disk" /></template>
