<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hvqy7zb2s.css';
import '../../css/f/fnvwt9cpi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXs9sYcjz"><g class="ufeehvblu"><path class="hvqy7zb2s"/><path class="fnvwt9cpi"/></g></mask></defs><path mask="url(#SVGXs9sYcjz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tag" /></template>
