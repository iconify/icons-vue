<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awiyetucd.css';
import '../../css/s/sak0m1nef.css';
import '../../css/e/ef7x2zbjy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtCKZFemV"><g clip-rule="evenodd" class="awiyetucd"><path class="sak0m1nef"/><path class="ef7x2zbjy"/></g></mask></defs><path mask="url(#SVGtCKZFemV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:vr-glasses" /></template>
