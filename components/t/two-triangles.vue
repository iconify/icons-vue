<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fpa8ojhka.css';
import '../../css/c/cqng7jbzi.css';
import '../../css/q/qi1-x1b4y.css';
import '../../css/u/u3lpmgb1x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxuPy0dzJ"><g class="ft5dv1b6b"><path class="fpa8ojhka"/><path class="cqng7jbzi"/><path class="qi1-x1b4y"/><path class="u3lpmgb1x"/></g></mask></defs><path mask="url(#SVGxuPy0dzJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:two-triangles" /></template>
