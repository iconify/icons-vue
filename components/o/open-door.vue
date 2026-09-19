<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fde0_4q6a.css';
import '../../css/z/z_1kwcpba.css';
import '../../css/c/cwm8rmbye.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjZUWBcHI"><g class="ufeehvblu"><path class="fde0_4q6a"/><path clip-rule="evenodd" class="z_1kwcpba"/><path class="cwm8rmbye"/></g></mask></defs><path mask="url(#SVGjZUWBcHI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:open-door" /></template>
