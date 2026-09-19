<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/dl6g4ybvr.css';
import '../../css/a/aac3rybxz.css';
import '../../css/y/y67g-971i.css';
import '../../css/v/v6kd6wt1k.css';
import '../../css/c/cz39jjkok.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9OxkTzUZ"><g class="s9cl3zbei"><ellipse class="dl6g4ybvr"/><ellipse transform="rotate(15 16.933 24.64)" class="aac3rybxz"/><ellipse transform="scale(-1 1)rotate(15 -109.047 -105.16)" class="y67g-971i"/><path class="v6kd6wt1k"/><path class="cz39jjkok"/></g></mask></defs><path mask="url(#SVG9OxkTzUZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:panda" /></template>
