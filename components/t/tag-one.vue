<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3mn7piaq.css';
import '../../css/k/kz8euhb7z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuw5dzeYm"><g class="ft5dv1b6b"><path class="k3mn7piaq"/><path clip-rule="evenodd" class="kz8euhb7z"/></g></mask></defs><path mask="url(#SVGuw5dzeYm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tag-one" /></template>
