<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et9p9tbwl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGah4dgkLO"><path class="et9p9tbwl"/></mask></defs><path mask="url(#SVGah4dgkLO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:one-one" /></template>
