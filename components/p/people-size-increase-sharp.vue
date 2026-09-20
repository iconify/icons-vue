<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt5jnvbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:people-size-increase-sharp" /></template>
<style>
.lt5jnvbjt {
  fill: currentColor;
  d: path("M17.346 19v-4.98h-1.404V9.944q0-.308.172-.548q.17-.24.488-.42t.787-.261t1.076-.081t1.073.08t.783.262t.489.422q.17.24.17.555v4.065h-1.403V19zm1.12-11.365q-.556 0-.953-.39t-.397-.939t.393-.938t.949-.387t.953.389t.397.94t-.393.937t-.95.387m-6.95 1.827q-.467 0-.789-.312q-.322-.313-.322-.784q0-.47.327-.783t.793-.313q.467 0 .789.313t.322.783t-.327.784t-.793.312m-6.457 1.423q-.371 0-.628-.247t-.257-.618t.257-.618t.628-.247q.37 0 .628.25t.256.615t-.256.615t-.628.25M10.635 19v-4.077H9.25V11.65q0-.288.146-.505q.146-.216.434-.372t.721-.233t.968-.078t.973.078q.439.077.731.233q.293.156.439.372q.146.217.146.505v3.273h-1.404V19zm-6.231 0v-3.154H3V12.91q0-.256.134-.458q.133-.202.4-.338q.269-.137.65-.212t.874-.075t.875.075t.648.212t.4.338q.135.202.135.458v2.936H5.712V19z");
}

</style>
