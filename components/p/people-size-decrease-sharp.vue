<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t80bxbbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:people-size-decrease-sharp" /></template>
<style>
.t80bxbbhw {
  fill: currentColor;
  d: path("M4.404 19v-4.98H3V9.944q0-.308.171-.548t.489-.42t.787-.261t1.076-.081t1.072.08t.784.262q.317.18.488.422q.172.24.172.555v4.065H6.635V19zm1.12-11.365q-.557 0-.954-.39q-.397-.389-.397-.939t.393-.938t.95-.387t.952.389q.398.389.398.94t-.394.937t-.949.387m6.934 1.827q-.466 0-.789-.312q-.322-.313-.322-.784q0-.47.327-.783t.793-.313q.467 0 .789.313q.322.312.322.783t-.327.784q-.326.312-.793.312m6.466 1.423q-.371 0-.628-.25q-.257-.251-.257-.615t.257-.614t.628-.251t.628.247t.257.618t-.257.618t-.628.247M11.577 19v-4.077h-1.404V11.65q0-.288.146-.505q.146-.216.437-.372q.29-.156.726-.233t.975-.078q.54 0 .972.078q.433.077.721.233t.435.372q.146.217.146.505v3.273h-1.385V19zm6.692 0v-3.154h-1.403V12.91q0-.256.133-.458q.134-.202.401-.338t.649-.212t.874-.075t.875.075t.648.212t.401.338t.134.458v2.936h-1.404V19z");
}

</style>
