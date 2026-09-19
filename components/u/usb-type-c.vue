<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/akm23jbon.css';
import '../../css/f/fwbu3rrnt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlxy0VdtO"><g class="aql7dnt-u"><path class="akm23jbon"/><path class="fwbu3rrnt"/></g></mask></defs><path mask="url(#SVGlxy0VdtO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:usb-type-c" /></template>
