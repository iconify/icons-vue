<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/s6uqvybtd.css';
import '../../css/h/hoxyj3bqy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGerbNUc4e"><g class="v3_i3wktz"><path class="s6uqvybtd"/><path class="hoxyj3bqy"/></g></mask></defs><path mask="url(#SVGerbNUc4e)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:table-file" /></template>
