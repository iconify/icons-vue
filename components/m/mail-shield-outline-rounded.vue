<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntpro__qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-shield-outline-rounded" /></template>
<style>
.ntpro__qw {
  fill: currentColor;
  d: path("M18.422 21.894q-.133-.025-.27-.08q-.573-.237-1.027-.623q-.454-.385-.821-.883q-.435-.61-.677-1.353q-.242-.744-.242-1.54V15.78q0-.218.108-.41t.326-.298l2.147-1.083q.348-.18.726-.18q.38 0 .727.18l2.147 1.083q.217.106.325.298t.109.41v1.636q0 .796-.233 1.54t-.667 1.353q-.367.498-.83.883q-.464.386-1.037.623q-.131.055-.267.08q-.137.025-.274.025t-.27-.025m.27-.898q1.087-.367 1.707-1.379t.62-2.202v-1.53l-2.327-1.154zM12 11l7.692-5H4.308zM4 6.564v.527v-.187V18v-6.865v.467v-4.698v.186v-.81v.04V6v.3v-.012zm-1 10.82V6.617q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.688q0 .287-.235.43t-.484.008q-.14-.067-.21-.183q-.071-.115-.071-.255v-4.4l-7.552 4.925q-.212.13-.448.13t-.448-.13L4 6.904v10.48q0 .27.173.443t.443.173h7.89q.213 0 .357.143t.143.357t-.143.357t-.357.143h-7.89q-.691 0-1.153-.462T3 17.384");
}

</style>
