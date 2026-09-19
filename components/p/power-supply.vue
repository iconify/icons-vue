<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/h/hehu1bb7z.css';
import '../../css/i/i-ufrdbxe.css';
import '../../css/l/locms3aej.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoFxlZdWE"><g class="wwvp95byt"><path class="hehu1bb7z"/><path class="i-ufrdbxe"/><path class="locms3aej"/></g></mask></defs><path mask="url(#SVGoFxlZdWE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:power-supply" /></template>
