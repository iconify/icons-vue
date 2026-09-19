<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/a/av9n8xbjy.css';
import '../../css/v/vzawncc4b.css';
import '../../css/u/uvj71_bha.css';
import '../../css/p/pu7g2dy4d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBntfNeAo"><g class="wwvp95byt"><path class="av9n8xbjy"/><path clip-rule="evenodd" class="vzawncc4b"/><path class="uvj71_bha"/><path class="pu7g2dy4d"/></g></mask></defs><path mask="url(#SVGBntfNeAo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:test-tube" /></template>
