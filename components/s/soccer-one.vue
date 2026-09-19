<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cflksfbjj.css';
import '../../css/m/mjfwmxbrm.css';
import '../../css/v/vsg7tgzjo.css';
import '../../css/v/va0oq6k-z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl5DUsIUC"><g class="ft5dv1b6b"><path class="cflksfbjj"/><path class="mjfwmxbrm"/><path class="vsg7tgzjo"/><path class="va0oq6k-z"/></g></mask></defs><path mask="url(#SVGl5DUsIUC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:soccer-one" /></template>
