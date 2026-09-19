<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3wwktf5z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHIMz2cTY"><path class="a3wwktf5z"/></mask></defs><path mask="url(#SVGHIMz2cTY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:two-two" /></template>
