<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/v/v9jvlqb3d.css';
import '../../css/f/fvk6mt17r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBObfBe1F"><g class="aql7dnt-u"><path class="v9jvlqb3d"/><rect class="fvk6mt17r"/></g></mask></defs><path mask="url(#SVGBObfBe1F)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:split" /></template>
