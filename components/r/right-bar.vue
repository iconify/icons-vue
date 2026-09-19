<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/y/y83q4pbpd.css';
import '../../css/x/x3aeq5y9b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzYdUId2F"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="y83q4pbpd"/><path class="x3aeq5y9b"/></g></mask></defs><path mask="url(#SVGzYdUId2F)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:right-bar" /></template>
