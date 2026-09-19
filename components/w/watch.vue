<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/g92amxlfl.css';
import '../../css/b/b_iq5obiy.css';
import '../../css/j/jdh9hhorp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcOaMObfg"><g class="aql7dnt-u"><path class="g92amxlfl"/><path class="b_iq5obiy"/><path class="jdh9hhorp"/></g></mask></defs><path mask="url(#SVGcOaMObfg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:watch" /></template>
