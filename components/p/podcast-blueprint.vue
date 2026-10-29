<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/v2vjkqb3x.css';
import '../../css/i/i7w7-7fxk.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/c/cf96073qd.css';
import '../../css/t/t3pi66bun.css';
import '../../css/h/hvhon2vds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="v2vjkqb3x wm-deco"/><path class="i7w7-7fxk wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="cf96073qd wm-k"/><path class="t3pi66bun wm-a"/><path class="hvhon2vds wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:podcast-blueprint" /></template>
