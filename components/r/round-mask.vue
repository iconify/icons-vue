<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/geju8gabu.css';
import '../../css/q/qz7nj6phs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAfVvubCX"><g class="aql7dnt-u"><path class="geju8gabu"/><path class="qz7nj6phs"/></g></mask></defs><path mask="url(#SVGAfVvubCX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:round-mask" /></template>
