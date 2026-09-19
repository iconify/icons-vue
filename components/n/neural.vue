<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/d4uzuxbeh.css';
import '../../css/e/e6fsqxbrk.css';
import '../../css/d/d4nb9cc3g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMaCf9bZC"><g class="s9cl3zbei"><path clip-rule="evenodd" class="d4uzuxbeh"/><path class="e6fsqxbrk"/><path class="d4nb9cc3g"/></g></mask></defs><path mask="url(#SVGMaCf9bZC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:neural" /></template>
