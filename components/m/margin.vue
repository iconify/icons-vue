<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/k/kb3uhrb5b.css';
import '../../css/q/q-u5w7bqk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGg6xLeIE"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="kb3uhrb5b"/><path class="q-u5w7bqk"/></g></mask></defs><path mask="url(#SVGGg6xLeIE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:margin" /></template>
