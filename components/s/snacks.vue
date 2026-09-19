<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x5qfqd5ld.css';
import '../../css/w/wujqs2ipr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6MK2Wb3V"><g class="v3_i3wktz"><path class="x5qfqd5ld"/><path class="wujqs2ipr"/></g></mask></defs><path mask="url(#SVG6MK2Wb3V)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:snacks" /></template>
