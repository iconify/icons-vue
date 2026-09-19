<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m1d7dbbiv.css';
import '../../css/q/qu0oflhiv.css';
import '../../css/u/u5f26dd-a.css';
import '../../css/m/m_qdoccqv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGI8Q5fshJ"><g class="ft5dv1b6b"><path class="m1d7dbbiv"/><path class="qu0oflhiv"/><path class="u5f26dd-a"/><path class="m_qdoccqv"/></g></mask></defs><path mask="url(#SVGI8Q5fshJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sapling" /></template>
