<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw26v2bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vacuum-2" /></template>
<style>
.mw26v2bxn {
  fill: currentColor;
  d: path("M12 11.808q.29 0 .51-.22t.22-.511q0-.31-.22-.52t-.51-.21q-.31 0-.52.21t-.21.52q0 .29.21.51t.52.22m-2.575 5.655h5.137l1.46 1.44q-.899.517-1.908.808Q13.104 20 12 20t-2.11-.29q-1.007-.29-1.906-.808zM12 4q1.644 0 3.099.636q1.455.635 2.542 1.723T19.365 8.9Q20 10.356 20 12q0 1.956-.858 3.591q-.857 1.636-2.284 2.732l-1.818-1.817q1.085-.729 1.744-1.914q.658-1.184.658-2.592q0-2.27-1.586-3.866T12 6.538T8.144 8.134T6.558 12q0 1.408.658 2.592q.659 1.185 1.744 1.914l-1.818 1.817q-1.426-1.096-2.284-2.732Q4 13.956 4 12q0-1.644.626-3.099T6.34 6.359t2.542-1.724Q10.337 4 12 4m0 3.539q1.842 0 3.152 1.309q1.31 1.31 1.31 3.152q0 1.862-1.31 3.162T12 16.462q-1.861 0-3.161-1.3T7.539 12q0-1.842 1.3-3.152T12 7.538");
}

</style>
