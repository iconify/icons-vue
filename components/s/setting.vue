<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrso7y3c.css';
import '../../css/s/sfp7mw5ut.css';
import '../../css/v/v3q5wob3k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVlwHzcpJ"><g class="ylrso7y3c"><path class="sfp7mw5ut"/><path class="v3q5wob3k"/></g></mask></defs><path mask="url(#SVGVlwHzcpJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:setting" /></template>
